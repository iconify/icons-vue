<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x37ks3dss.css';
import '../../css/i/i8iix-ktc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x37ks3dss"/><path clip-rule="evenodd" class="i8iix-ktc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-left-detailed-fill" /></template>
