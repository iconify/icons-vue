<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-n60hb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-n60hb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bandcamp-logo-2-block" /></template>
