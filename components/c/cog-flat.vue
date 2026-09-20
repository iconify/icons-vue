<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdje1zcva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pdje1zcva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:cog-flat" /></template>
