<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8pgvmb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k8pgvmb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrows-right-left" /></template>
