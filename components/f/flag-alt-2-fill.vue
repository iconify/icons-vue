<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9sfjmbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9sfjmbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flag-alt-2-fill" /></template>
