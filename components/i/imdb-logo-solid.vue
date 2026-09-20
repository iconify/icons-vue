<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccfj4q6iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ccfj4q6iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:imdb-logo-solid" /></template>
