<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-h4btj8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-h4btj8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-cat-solid" /></template>
