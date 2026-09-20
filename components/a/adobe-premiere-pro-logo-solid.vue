<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu60kgxto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wu60kgxto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-premiere-pro-logo-solid" /></template>
