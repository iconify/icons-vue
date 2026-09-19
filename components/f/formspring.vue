<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujjvzsbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":488};
const content = `<path class="ujjvzsbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:formspring" /></template>
