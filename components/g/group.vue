<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgb4m8j_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hgb4m8j_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:group" /></template>
