<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/albzziifn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="albzziifn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:add-1-remix" /></template>
