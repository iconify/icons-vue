<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txdk-rk8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txdk-rk8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-databricks" /></template>
