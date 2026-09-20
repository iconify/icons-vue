<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu1kso72z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pu1kso72z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fortress" /></template>
