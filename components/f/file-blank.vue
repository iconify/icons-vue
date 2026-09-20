<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykexaabqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykexaabqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-blank" /></template>
