<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rln3ffbom.css';
import '../../css/x/xxfcmckbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rln3ffbom"/><path class="xxfcmckbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cast-20" /></template>
