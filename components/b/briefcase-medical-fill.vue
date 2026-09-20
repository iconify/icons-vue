<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxfzyid1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fxfzyid1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:briefcase-medical-fill" /></template>
