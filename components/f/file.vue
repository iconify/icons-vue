<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8lqozphz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":512};
const content = `<path class="k8lqozphz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:file" /></template>
