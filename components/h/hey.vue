<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7l6-9b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7l6-9b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hey" /></template>
