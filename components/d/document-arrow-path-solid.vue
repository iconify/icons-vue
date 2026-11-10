<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjyan90lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bjyan90lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:document-arrow-path-solid" /></template>
