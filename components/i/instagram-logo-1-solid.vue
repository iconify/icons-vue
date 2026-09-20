<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt3uecrng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pt3uecrng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:instagram-logo-1-solid" /></template>
