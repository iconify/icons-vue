<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhog3w6ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qhog3w6ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-talk-logo-block" /></template>
