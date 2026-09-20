<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l20qj3sjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l20qj3sjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bear-spray-can-with-spray-and-pound" /></template>
