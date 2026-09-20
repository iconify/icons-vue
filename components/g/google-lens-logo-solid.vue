<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq_pwhb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xq_pwhb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-lens-logo-solid" /></template>
