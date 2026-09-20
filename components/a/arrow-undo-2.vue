<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysf88hb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysf88hb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-undo-2" /></template>
