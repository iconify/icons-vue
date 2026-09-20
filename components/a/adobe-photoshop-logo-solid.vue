<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjxwheahl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zjxwheahl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-photoshop-logo-solid" /></template>
