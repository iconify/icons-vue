<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r629fq0ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r629fq0ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x2-sharp-fill" /></template>
