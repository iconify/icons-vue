<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk_mpr0sg.css';
import '../../css/q/qvws5acex.css';
import '../../css/v/vf-yj3bws.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 sk_mpr0sg"/><path class="clr-i-outline clr-i-outline-path-2 qvws5acex"/><path class="clr-i-outline clr-i-outline-path-3 vf-yj3bws"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:help-info-line" /></template>
