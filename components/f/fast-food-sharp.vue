<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flab64b9x.css';
import '../../css/e/eehn7s3el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="flab64b9x"/><path class="eehn7s3el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:fast-food-sharp" /></template>
