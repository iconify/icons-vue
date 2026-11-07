<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3zoptn7o.css';
import '../../css/g/gc83r37zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3zoptn7o"/><path class="gc83r37zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-bold-duotone" /></template>
