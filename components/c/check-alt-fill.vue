<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gigmts-4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gigmts-4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:check-alt-fill" /></template>
