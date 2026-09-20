<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frp_2fbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="frp_2fbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:align-right" /></template>
