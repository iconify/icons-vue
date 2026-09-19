<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf6dpzmng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bf6dpzmng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:building-2" /></template>
