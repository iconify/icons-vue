<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_kfb9bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_kfb9bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:flag" /></template>
