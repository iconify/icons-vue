<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gojyo4b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gojyo4b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:foursquare-logo-1-block" /></template>
