<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_mrlqbtl.css';
import '../../css/o/om6kf4uvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_mrlqbtl"/><path class="om6kf4uvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:arrow-up" /></template>
