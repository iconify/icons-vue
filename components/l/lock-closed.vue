<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sinmak_xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sinmak_xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:lock-closed" /></template>
