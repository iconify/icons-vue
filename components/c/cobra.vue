<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk5o4h72k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bk5o4h72k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cobra" /></template>
