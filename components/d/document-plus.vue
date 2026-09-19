<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cprfqybem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cprfqybem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:document-plus" /></template>
