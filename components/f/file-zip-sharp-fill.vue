<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iftoou-8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iftoou-8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-zip-sharp-fill" /></template>
