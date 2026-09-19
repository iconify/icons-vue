<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx7oyrbof.css';
import '../../css/m/mb0x8lb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="dx7oyrbof"/><path class="mb0x8lb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:info-filled" /></template>
