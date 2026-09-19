<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9tfbnbmz.css';
import '../../css/p/pmrsduv8z.css';
import '../../css/v/v5czncb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f9tfbnbmz"/><path class="pmrsduv8z"/><path class="v5czncb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-heart-dislike" /></template>
