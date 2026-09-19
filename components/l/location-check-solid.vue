<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz86kxbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lz86kxbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:location-check-solid" /></template>
