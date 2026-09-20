<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t519rybsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t519rybsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:code-2-outline" /></template>
