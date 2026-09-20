<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4p_vim0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4p_vim0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cart-minus-solid" /></template>
