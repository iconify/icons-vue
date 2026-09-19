<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr1eulbdl.css';
import '../../css/z/z6nvbo_3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr1eulbdl"/><path class="z6nvbo_3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chevron-double-up-alt" /></template>
