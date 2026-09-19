<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd6sfoi7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd6sfoi7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-user-minus" /></template>
