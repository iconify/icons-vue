<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4r2-ed2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4r2-ed2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:google-hangouts-alt" /></template>
