<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn857q1xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kn857q1xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:folder-check-remix" /></template>
