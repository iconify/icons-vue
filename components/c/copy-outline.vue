<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs-ufny6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs-ufny6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:copy-outline" /></template>
