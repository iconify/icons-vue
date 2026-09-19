<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8_l-zb6q.css';
import '../../css/v/v0ztzdxtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8_l-zb6q"/><path class="v0ztzdxtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-dog" /></template>
