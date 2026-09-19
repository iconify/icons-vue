<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te_6-yblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="te_6-yblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fluxbb" /></template>
