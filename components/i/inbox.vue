<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5huyu70j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":750};
const content = `<path class="c5huyu70j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:inbox" /></template>
