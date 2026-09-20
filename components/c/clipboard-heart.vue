<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k76g5dgpz.css';
import '../../css/l/lm9ywsb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k76g5dgpz"/><path class="lm9ywsb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:clipboard-heart" /></template>
