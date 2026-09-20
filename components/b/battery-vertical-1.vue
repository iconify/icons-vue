<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad19tgbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad19tgbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-vertical-1" /></template>
