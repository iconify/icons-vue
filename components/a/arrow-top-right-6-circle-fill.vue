<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0hfgbc0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k0hfgbc0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-right-6-circle-fill" /></template>
