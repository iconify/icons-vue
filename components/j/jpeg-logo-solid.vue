<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo6wm__mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mo6wm__mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:jpeg-logo-solid" /></template>
