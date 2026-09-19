<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isdc2k3ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1504};
const content = `<path class="isdc2k3ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:github" /></template>
