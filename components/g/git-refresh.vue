<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3k87mqng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3k87mqng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-refresh" /></template>
