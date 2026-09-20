<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc2_j6ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc2_j6ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-tablet-filled" /></template>
