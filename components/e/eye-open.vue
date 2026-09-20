<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-h8uebox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v-h8uebox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:eye-open" /></template>
