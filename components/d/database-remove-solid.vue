<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9ffhot1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c9ffhot1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:database-remove-solid" /></template>
