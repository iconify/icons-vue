<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dstdqz7pa.css';
import '../../css/p/prmb0_bed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dstdqz7pa duoicon-secondary-layer"/><path class="duoicon-primary-layer prmb0_bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:alert-octagon" /></template>
