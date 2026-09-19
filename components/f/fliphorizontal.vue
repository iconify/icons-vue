<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp0e_-bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rp0e_-bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fliphorizontal" /></template>
