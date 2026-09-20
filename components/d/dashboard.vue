<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkb9m2b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wkb9m2b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:dashboard" /></template>
