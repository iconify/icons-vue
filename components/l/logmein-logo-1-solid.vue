<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0avydbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w0avydbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:logmein-logo-1-solid" /></template>
