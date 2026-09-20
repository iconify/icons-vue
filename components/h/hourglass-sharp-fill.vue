<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saeb17b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saeb17b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hourglass-sharp-fill" /></template>
