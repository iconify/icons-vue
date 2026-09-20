<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywxi7zk5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywxi7zk5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-font-size-increase" /></template>
