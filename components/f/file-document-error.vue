<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp67l1bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp67l1bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-document-error" /></template>
