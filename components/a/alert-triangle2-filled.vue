<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exhuzbbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="exhuzbbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:alert-triangle2-filled" /></template>
