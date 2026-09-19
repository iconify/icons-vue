<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwnpb3bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":560,"height":850};
const content = `<path class="fwnpb3bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:book" /></template>
