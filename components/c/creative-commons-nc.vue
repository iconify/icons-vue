<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm9-6ac6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qm9-6ac6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:creative-commons-nc" /></template>
