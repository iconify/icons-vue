<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2dsus3eh.css';
import '../../css/m/mh2gjorsd.css';
import '../../css/h/h7vs4zvyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e2dsus3eh"/><path class="mh2gjorsd"/><path class="h7vs4zvyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bitwarden-portal" /></template>
