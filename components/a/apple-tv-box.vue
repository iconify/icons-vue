<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghl62r_kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghl62r_kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:apple-tv-box" /></template>
