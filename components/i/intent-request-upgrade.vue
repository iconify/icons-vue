<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnecdetti.css';
import '../../css/a/arfms3bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tnecdetti"/><path class="arfms3bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:intent-request-upgrade" /></template>
