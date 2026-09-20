<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pracb0xpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pracb0xpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-mark-as-unread" /></template>
