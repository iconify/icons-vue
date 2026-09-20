<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0etpyb4l.css';
import '../../css/d/dkp-fpbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c0etpyb4l"/><path class="dkp-fpbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:heyform-light" /></template>
