<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv52_k8xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv52_k8xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-single-fill" /></template>
