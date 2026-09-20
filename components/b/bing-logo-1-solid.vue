<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaqf9wbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uaqf9wbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bing-logo-1-solid" /></template>
