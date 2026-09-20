<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhj3n1bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lhj3n1bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:instapaper-logo-block" /></template>
