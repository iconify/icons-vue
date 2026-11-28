<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-pb3-s-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-pb3-s-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-input-solid" /></template>
