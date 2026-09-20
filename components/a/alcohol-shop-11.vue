<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htc46chub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="htc46chub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:alcohol-shop-11" /></template>
