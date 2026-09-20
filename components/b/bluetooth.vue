<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_8ijoebc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="a_8ijoebc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bluetooth" /></template>
