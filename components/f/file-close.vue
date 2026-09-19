<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwj7h0bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwj7h0bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:file-close" /></template>
