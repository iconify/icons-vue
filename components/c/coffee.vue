<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezlrxrblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1856,"height":1408};
const content = `<path class="ezlrxrblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:coffee" /></template>
