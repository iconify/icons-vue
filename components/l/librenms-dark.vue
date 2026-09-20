<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7vzaig-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h7vzaig-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librenms-dark" /></template>
