<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7to8j3eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7to8j3eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-top-center-filled" /></template>
