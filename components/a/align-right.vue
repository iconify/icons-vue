<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyjy1tb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-7};
const content = `<path class="xyjy1tb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:align-right" /></template>
