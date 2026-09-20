<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi46hz2yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fi46hz2yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:elixir-16" /></template>
