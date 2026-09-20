<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y21npvxed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y21npvxed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:image-highlights-solid" /></template>
