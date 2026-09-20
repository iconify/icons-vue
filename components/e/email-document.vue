<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dje-5vern.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="dje-5vern"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:email-document" /></template>
