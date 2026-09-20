<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbkzf60tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zbkzf60tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-with-yen-yuan" /></template>
