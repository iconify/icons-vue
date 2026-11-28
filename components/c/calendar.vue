<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz_yk4vtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz_yk4vtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:calendar" /></template>
