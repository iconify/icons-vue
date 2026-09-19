<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zet6c8b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zet6c8b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cart-minus-filled" /></template>
