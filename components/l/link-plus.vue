<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcc653a5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcc653a5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:link-plus" /></template>
