<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b63zbiv_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b63zbiv_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:elastic-cloud-logo-solid" /></template>
