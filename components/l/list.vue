<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e07hgxwrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e07hgxwrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:list" /></template>
