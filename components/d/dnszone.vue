<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wap9h4bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wap9h4bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dnszone" /></template>
