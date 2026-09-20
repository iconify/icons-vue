<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haf8sabek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="haf8sabek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bank-jp-11" /></template>
