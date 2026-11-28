<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w13d4acuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w13d4acuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-open" /></template>
