<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju3o7zbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju3o7zbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:google-wallet" /></template>
