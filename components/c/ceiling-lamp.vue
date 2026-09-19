<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuj2j6pai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuj2j6pai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-lamp" /></template>
