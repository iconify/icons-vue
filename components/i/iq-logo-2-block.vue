<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uodgz0val.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uodgz0val"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:iq-logo-2-block" /></template>
