<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvvj__u4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xvvj__u4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lamb" /></template>
