<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6io-gzjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6io-gzjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clear-all-line" /></template>
