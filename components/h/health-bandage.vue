<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byt1vbcft.css';
import '../../css/u/ue2etpb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="byt1vbcft"/><path class="ue2etpb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-bandage" /></template>
