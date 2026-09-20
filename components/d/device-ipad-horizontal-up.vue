<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4gquy6oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4gquy6oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-horizontal-up" /></template>
