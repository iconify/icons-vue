<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujx4dsesw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ujx4dsesw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:border-style" /></template>
