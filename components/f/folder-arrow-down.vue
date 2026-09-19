<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rld_-7kyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rld_-7kyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:folder-arrow-down" /></template>
