<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c09546l0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="c09546l0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bookalt" /></template>
