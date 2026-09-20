<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i79vyfvhr.css';
import '../../css/y/yuh6-fbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="i79vyfvhr"/><path class="yuh6-fbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:imaging-alternative-ct" /></template>
