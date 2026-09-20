<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwm-7vbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zwm-7vbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:key3-filled" /></template>
