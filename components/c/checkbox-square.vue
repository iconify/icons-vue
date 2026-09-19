<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af1k-_boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af1k-_boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:checkbox-square" /></template>
