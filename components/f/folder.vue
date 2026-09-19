<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7bywp-mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":740,"height":800};
const content = `<path class="h7bywp-mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:folder" /></template>
