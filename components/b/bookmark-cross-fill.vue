<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-7jaubeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-7jaubeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:bookmark-cross-fill" /></template>
