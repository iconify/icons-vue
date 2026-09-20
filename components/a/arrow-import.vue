<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vql-jj_cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vql-jj_cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-import" /></template>
