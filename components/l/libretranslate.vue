<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azhznbcrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="azhznbcrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:libretranslate" /></template>
