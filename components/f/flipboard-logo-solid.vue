<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9w3oobaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u9w3oobaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:flipboard-logo-solid" /></template>
