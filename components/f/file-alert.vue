<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfnt_40zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfnt_40zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-alert" /></template>
