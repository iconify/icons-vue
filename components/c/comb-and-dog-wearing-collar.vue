<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmiwzssgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bmiwzssgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:comb-and-dog-wearing-collar" /></template>
