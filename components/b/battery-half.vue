<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwb5pczfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uwb5pczfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:battery-half" /></template>
