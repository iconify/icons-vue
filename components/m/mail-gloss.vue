<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqit36bxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqit36bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mail-gloss" /></template>
