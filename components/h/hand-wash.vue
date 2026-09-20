<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvoe02p8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvoe02p8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-wash" /></template>
