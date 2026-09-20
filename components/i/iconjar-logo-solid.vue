<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlkw1s6vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dlkw1s6vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:iconjar-logo-solid" /></template>
