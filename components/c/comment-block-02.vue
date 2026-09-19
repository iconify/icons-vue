<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elcyv1bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elcyv1bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:comment-block-02" /></template>
