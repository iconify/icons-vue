<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elyhgxbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="elyhgxbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cat-1-solid" /></template>
