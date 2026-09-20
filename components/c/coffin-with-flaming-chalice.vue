<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4qgvpbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z4qgvpbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coffin-with-flaming-chalice" /></template>
