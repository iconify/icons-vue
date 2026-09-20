<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp25m2b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp25m2b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-f-filled" /></template>
