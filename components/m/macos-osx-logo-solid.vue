<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeu22r-zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeu22r-zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:macos-osx-logo-solid" /></template>
