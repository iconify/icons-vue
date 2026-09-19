<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl_69iu2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl_69iu2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:collection" /></template>
