<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8ux7eavv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t8ux7eavv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-xd-logo-solid" /></template>
