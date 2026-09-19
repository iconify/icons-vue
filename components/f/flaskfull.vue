<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs_o25eyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1024};
const content = `<path class="vs_o25eyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:flaskfull" /></template>
