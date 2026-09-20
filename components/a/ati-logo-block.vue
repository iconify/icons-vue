<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjrm1iu6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gjrm1iu6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:ati-logo-block" /></template>
