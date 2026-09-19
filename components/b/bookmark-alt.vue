<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja00h22ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja00h22ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bookmark-alt" /></template>
