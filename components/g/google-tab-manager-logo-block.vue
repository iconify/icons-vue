<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsctvp7wz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jsctvp7wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-tab-manager-logo-block" /></template>
