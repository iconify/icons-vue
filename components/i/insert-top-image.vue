<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krdf7zkuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krdf7zkuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:insert-top-image" /></template>
