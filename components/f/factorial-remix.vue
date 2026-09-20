<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj-v6nbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cj-v6nbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:factorial-remix" /></template>
