<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui9v0tb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui9v0tb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flashlight-fill" /></template>
