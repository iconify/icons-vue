<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bigfy4btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bigfy4btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gumroad-line" /></template>
