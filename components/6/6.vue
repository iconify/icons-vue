<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uswx_e-5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uswx_e-5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:6" /></template>
