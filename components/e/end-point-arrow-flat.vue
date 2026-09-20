<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvvd8ubjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bvvd8ubjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:end-point-arrow-flat" /></template>
