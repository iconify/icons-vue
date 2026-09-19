<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l723oeeow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l723oeeow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:attachment-fill" /></template>
