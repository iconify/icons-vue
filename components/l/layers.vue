<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxw46px4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hxw46px4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:layers" /></template>
