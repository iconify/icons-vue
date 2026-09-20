<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8yvu7bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t8yvu7bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:fork-knife-remix" /></template>
