<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acpb1078r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="acpb1078r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:four-four" /></template>
