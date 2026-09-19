<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke9bzzbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":870,"height":1000};
const content = `<path class="ke9bzzbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-grin" /></template>
