<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwsc7mbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lwsc7mbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:google-drive-solid" /></template>
