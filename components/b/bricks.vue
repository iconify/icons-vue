<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwd_jac5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="xwd_jac5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bricks" /></template>
