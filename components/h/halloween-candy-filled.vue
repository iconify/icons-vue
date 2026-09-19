<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xptlr6bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xptlr6bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-candy-filled" /></template>
