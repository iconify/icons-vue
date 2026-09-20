<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq-ctd02e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="iq-ctd02e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:emote-happy-filled" /></template>
