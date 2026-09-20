<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1ut0ub3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b1ut0ub3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fish-beside-sausage" /></template>
