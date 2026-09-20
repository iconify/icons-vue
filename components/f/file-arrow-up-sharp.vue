<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0ycukbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0ycukbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-arrow-up-sharp" /></template>
