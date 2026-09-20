<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr_y9gxnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr_y9gxnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:helix" /></template>
