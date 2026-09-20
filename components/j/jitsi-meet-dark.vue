<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8z549mku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i8z549mku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jitsi-meet-dark" /></template>
