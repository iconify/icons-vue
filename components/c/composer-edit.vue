<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnglojbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dnglojbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:composer-edit" /></template>
