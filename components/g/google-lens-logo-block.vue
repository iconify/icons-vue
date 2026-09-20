<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btdx5vb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="btdx5vb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-lens-logo-block" /></template>
