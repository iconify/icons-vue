<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7inaiblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n7inaiblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:design-bump-logo-solid" /></template>
