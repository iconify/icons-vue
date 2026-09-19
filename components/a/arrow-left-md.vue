<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n99jjq5wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n99jjq5wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-left-md" /></template>
