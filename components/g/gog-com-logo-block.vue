<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk3ez3bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mk3ez3bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:gog-com-logo-block" /></template>
