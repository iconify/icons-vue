<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkc7o_b9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkc7o_b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-minus" /></template>
