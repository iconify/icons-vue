<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzjhb4vdg.css';
import '../../css/n/naokebl4y.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 dzjhb4vdg"/><path class="clr-i-outline clr-i-outline-path-2 naokebl4y"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:flag-line" /></template>
