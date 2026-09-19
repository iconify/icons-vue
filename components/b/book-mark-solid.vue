<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3415pcbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n3415pcbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:book-mark-solid" /></template>
