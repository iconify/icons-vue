<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rldg7kble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="rldg7kble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:icecream" /></template>
