<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idhksyb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="idhksyb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:discord-logo-2-solid" /></template>
