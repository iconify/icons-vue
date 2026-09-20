<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxd616xaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxd616xaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-left-sharp" /></template>
