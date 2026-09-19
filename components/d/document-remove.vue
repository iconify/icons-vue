<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8krlm47t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k8krlm47t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:document-remove" /></template>
