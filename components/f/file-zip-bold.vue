<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj1cjk89h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jj1cjk89h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-zip-bold" /></template>
