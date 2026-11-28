<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmt0y9b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmt0y9b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:gamepad-heart" /></template>
