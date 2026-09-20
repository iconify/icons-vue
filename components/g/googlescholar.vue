<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf2mwhv5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf2mwhv5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googlescholar" /></template>
