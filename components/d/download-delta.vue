<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3h213bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h3h213bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:download-delta" /></template>
