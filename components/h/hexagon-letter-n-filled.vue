<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcmnq--uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcmnq--uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-n-filled" /></template>
