<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk1m2mpra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk1m2mpra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:airpods-fill" /></template>
