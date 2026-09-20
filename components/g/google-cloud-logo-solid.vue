<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy1g-5rhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cy1g-5rhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-cloud-logo-solid" /></template>
