<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzw-n1jqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gzw-n1jqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-audio-sharp-fill" /></template>
