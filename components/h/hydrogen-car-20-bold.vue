<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1pfy_bym.css';
import '../../css/f/fsw4fslqf.css';
import '../../css/z/z_svvovos.css';
import '../../css/c/cxc03ab-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s1pfy_bym"/><path class="fsw4fslqf"/><path class="z_svvovos"/><path class="cxc03ab-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-car-20-bold" /></template>
