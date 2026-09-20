<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo52jq6wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jo52jq6wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-near-by-logo-solid" /></template>
