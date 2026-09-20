<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6s395bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6s395bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:github-logo-2-solid" /></template>
