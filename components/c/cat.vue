<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw-bh2b7p.css';
import '../../css/r/rmwwi5nky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw-bh2b7p"/><path class="rmwwi5nky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cat" /></template>
