<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hanj1gb4h.css';
import '../../css/e/egoxdachk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hanj1gb4h"/><path class="egoxdachk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-washer" /></template>
