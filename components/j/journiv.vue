<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feh17ircu.css';
import '../../css/v/vbxcdz47q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="feh17ircu"/><path class="vbxcdz47q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:journiv" /></template>
