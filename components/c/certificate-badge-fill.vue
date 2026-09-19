<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqm7u3bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wqm7u3bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:certificate-badge-fill" /></template>
