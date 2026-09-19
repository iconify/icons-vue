<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drlghjk_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drlghjk_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:friends-of-hue-retrotouch-black-plain" /></template>
