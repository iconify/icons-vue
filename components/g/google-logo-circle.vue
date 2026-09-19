<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_zb_yo5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_zb_yo5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:google-logo-circle" /></template>
