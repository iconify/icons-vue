<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-vmlkb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-vmlkb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:contact-center-ai" /></template>
