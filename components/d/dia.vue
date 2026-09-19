<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr9cd_urf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hr9cd_urf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:dia" /></template>
