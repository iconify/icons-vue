<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iufw5acos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iufw5acos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-down" /></template>
