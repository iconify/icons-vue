<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na5e8db9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="na5e8db9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:alert-square-filled" /></template>
