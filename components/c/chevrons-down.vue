<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0oqxmb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="w0oqxmb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevrons-down" /></template>
