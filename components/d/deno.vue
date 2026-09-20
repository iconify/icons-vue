<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt759hbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt759hbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:deno" /></template>
