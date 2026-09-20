<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq49l7bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vq49l7bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:basecamp-logo-2-solid" /></template>
