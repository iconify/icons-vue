<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzupgv2cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zzupgv2cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:behance-logo-block" /></template>
