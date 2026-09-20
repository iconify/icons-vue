<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj923kb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mj923kb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:linkedin-logo-block" /></template>
