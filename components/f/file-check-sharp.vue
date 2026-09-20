<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_xunb2ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_xunb2ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-check-sharp" /></template>
