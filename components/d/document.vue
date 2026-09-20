<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grs2zwbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="grs2zwbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:document" /></template>
