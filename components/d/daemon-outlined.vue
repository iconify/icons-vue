<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvb50glwu.css';
import '../../css/f/fj1-tkbqz.css';
import '../../css/h/hwoc3ibiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvb50glwu"/><path class="fj1-tkbqz"/><path class="hwoc3ibiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:daemon-outlined" /></template>
