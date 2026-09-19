<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehtknl-of.css';
import '../../css/k/kxd8gsbwd.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 ehtknl-of"/><path class="clr-i-outline clr-i-outline-path-2 kxd8gsbwd"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:bell-curve-line" /></template>
