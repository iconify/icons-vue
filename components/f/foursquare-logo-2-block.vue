<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds9k9lg1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ds9k9lg1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:foursquare-logo-2-block" /></template>
