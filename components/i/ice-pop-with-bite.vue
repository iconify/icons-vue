<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s56hofbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s56hofbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ice-pop-with-bite" /></template>
