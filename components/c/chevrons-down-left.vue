<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef5jcs_rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="ef5jcs_rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevrons-down-left" /></template>
