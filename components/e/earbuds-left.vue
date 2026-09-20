<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdgbeebqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xdgbeebqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:earbuds-left" /></template>
