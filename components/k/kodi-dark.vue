<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_ueecbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h_ueecbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kodi-dark" /></template>
