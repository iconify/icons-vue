<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apkxewmoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apkxewmoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:instapaper-logo-solid" /></template>
