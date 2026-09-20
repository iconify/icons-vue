<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsz6-0r-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsz6-0r-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:dropbox-logo-1-block" /></template>
