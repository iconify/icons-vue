<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfrefdafx.css';
import '../../css/c/cion4p3li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gfrefdafx"/><path class="cion4p3li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fmd-dark" /></template>
