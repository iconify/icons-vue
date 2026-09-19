<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngp646uqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":512};
const content = `<path class="ngp646uqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ckeditor" /></template>
