<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plrv83b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="plrv83b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:information-circle" /></template>
