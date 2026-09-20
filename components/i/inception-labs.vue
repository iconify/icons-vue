<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijn9g66do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijn9g66do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:inception-labs" /></template>
