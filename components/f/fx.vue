<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt10cwbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="vt10cwbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fx" /></template>
