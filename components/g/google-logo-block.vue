<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh_0sfwki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lh_0sfwki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-logo-block" /></template>
