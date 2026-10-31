<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbm-2zbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbm-2zbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-tiger-gloss" /></template>
