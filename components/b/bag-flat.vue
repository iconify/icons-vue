<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyca08b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eyca08b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:bag-flat" /></template>
