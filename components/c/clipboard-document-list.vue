<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdgw8wb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdgw8wb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:clipboard-document-list" /></template>
