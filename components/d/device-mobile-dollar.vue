<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj38nmb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj38nmb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-mobile-dollar" /></template>
