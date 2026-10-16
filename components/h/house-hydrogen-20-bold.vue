<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gro8lebrz.css';
import '../../css/k/kifto8buo.css';
import '../../css/g/geksxacrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gro8lebrz"/><path class="kifto8buo"/><path class="geksxacrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-hydrogen-20-bold" /></template>
