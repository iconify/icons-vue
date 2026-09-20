<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1qdurbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1qdurbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:keep-a-changelog" /></template>
