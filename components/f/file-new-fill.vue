<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m52v13bya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m52v13bya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-new-fill" /></template>
