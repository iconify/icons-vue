<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ualv6vazw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ualv6vazw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:location-pin-alt" /></template>
