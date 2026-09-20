<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du7gv6bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du7gv6bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:cloud-transfer-half" /></template>
