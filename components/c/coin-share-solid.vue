<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhqe0-kgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bhqe0-kgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:coin-share-solid" /></template>
