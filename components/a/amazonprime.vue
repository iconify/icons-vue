<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz_weoi3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz_weoi3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:amazonprime" /></template>
