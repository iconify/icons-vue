<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkpmi-kbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkpmi-kbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:android-logo-solid" /></template>
