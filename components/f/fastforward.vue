<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys5e_r7yr.css';
import '../../css/e/ey1v8gbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":12};
const content = `<path class="ys5e_r7yr"/><path class="ey1v8gbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:fastforward" /></template>
