<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdgye8b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kdgye8b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-up-solid" /></template>
