<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9rz68q5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w9rz68q5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:corners" /></template>
