<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpws0u1gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpws0u1gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:headspace" /></template>
