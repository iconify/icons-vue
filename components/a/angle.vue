<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5gnfbb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i5gnfbb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:angle" /></template>
