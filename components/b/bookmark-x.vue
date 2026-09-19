<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9kt7zn7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9kt7zn7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bookmark-x" /></template>
