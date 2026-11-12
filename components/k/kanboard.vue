<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v25mscwtj.css';
import '../../css/f/fkzaws_nc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v25mscwtj"/><path class="fkzaws_nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kanboard" /></template>
