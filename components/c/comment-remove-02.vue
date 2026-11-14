<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0d8nnbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0d8nnbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:comment-remove-02" /></template>
