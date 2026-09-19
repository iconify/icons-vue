<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viruazbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":424,"height":432};
const content = `<path class="viruazbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:google" /></template>
