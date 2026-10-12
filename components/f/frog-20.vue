<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceq48ugul.css';
import '../../css/k/kw7672rxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ceq48ugul"/><path class="kw7672rxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:frog-20" /></template>
