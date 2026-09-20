<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg8ti8thn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg8ti8thn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-left-thick" /></template>
