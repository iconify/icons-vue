<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afw-zzyvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="afw-zzyvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:hourglass" /></template>
