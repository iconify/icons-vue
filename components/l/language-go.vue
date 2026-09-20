<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaig0zbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaig0zbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-go" /></template>
