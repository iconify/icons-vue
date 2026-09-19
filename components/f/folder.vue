<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_44zqbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1391,"height":1000};
const content = `<path class="x_44zqbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:folder" /></template>
