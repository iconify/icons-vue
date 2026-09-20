<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0e5g6bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b0e5g6bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:foursquare-logo-solid" /></template>
