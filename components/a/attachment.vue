<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns0o8vbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ns0o8vbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:attachment" /></template>
