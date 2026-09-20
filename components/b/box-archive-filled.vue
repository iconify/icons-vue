<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcg1skb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcg1skb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:box-archive-filled" /></template>
