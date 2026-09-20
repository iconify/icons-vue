<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq10kcy8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mq10kcy8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:facebook-dark" /></template>
