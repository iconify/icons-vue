<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivwl1-arg.css';
import '../../css/z/z7-npobbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivwl1-arg"/><path class="z7-npobbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:car" /></template>
