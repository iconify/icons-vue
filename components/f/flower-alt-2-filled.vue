<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9yn-b0zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9yn-b0zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:flower-alt-2-filled" /></template>
