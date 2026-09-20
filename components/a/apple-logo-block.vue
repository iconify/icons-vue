<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smfu5rbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="smfu5rbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:apple-logo-block" /></template>
