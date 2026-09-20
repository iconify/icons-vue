<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pveghdbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pveghdbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:irc-galleria-logo-block" /></template>
