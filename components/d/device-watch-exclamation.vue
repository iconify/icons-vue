<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky8f96b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky8f96b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-watch-exclamation" /></template>
