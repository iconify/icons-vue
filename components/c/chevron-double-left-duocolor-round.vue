<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b73s-ci7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b73s-ci7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-double-left-duocolor-round" /></template>
