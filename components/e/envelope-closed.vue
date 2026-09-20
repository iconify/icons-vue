<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bidf0ubeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bidf0ubeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:envelope-closed" /></template>
