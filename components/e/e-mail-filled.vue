<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk-bu9-no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="dk-bu9-no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:e-mail-filled" /></template>
