<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly4bitb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ly4bitb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:libretranslate-dark" /></template>
