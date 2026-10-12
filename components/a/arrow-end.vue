<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyu31v5md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyu31v5md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrow-end" /></template>
