<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jteh5fb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jteh5fb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:archive-restore-solid" /></template>
