<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up3gczb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="up3gczb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:flickr-logo-solid" /></template>
