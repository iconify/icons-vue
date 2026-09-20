<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk8is5but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zk8is5but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:beats-studio-logo-solid" /></template>
