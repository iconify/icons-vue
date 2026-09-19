<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr-36j6gx.css';
import '../../css/z/zw8k7krbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr-36j6gx"/><path class="zw8k7krbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:backspace" /></template>
