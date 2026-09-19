<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8zy_rbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8zy_rbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:double-window-closed" /></template>
