<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1f5b8moy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1f5b8moy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-5-round" /></template>
