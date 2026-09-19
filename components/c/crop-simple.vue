<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzobl5bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kzobl5bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:crop-simple" /></template>
