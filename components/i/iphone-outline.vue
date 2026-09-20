<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar8us1vws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ar8us1vws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:iphone-outline" /></template>
