<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_4s31bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_4s31bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kick-scooter-broken" /></template>
