<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epd150b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="epd150b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:ellipsis-h-light" /></template>
