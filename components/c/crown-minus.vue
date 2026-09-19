<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmf7asbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="xmf7asbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:crown-minus" /></template>
