<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4l6eub2n.css';
import '../../css/c/c8caqzgai.css';
import '../../css/u/ug-lui25o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="m4l6eub2n"/><path class="c8caqzgai"/><path class="ug-lui25o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:de-4x3" /></template>
