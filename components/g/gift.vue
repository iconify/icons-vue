<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyde7_dhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nyde7_dhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:gift" /></template>
