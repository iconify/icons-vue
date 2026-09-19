<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz946rb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="yz946rb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:gift" /></template>
