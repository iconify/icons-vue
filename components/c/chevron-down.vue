<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgilk566a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-8};
const content = `<path class="tgilk566a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevron-down" /></template>
