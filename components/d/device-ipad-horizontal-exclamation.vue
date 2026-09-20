<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds4ebdc8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds4ebdc8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-horizontal-exclamation" /></template>
