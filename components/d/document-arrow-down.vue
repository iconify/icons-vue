<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtu4mioil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtu4mioil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-arrow-down" /></template>
