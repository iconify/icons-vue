<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_o4c-fyf.css';
import '../../css/b/bafc_qt6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_o4c-fyf"/><path class="bafc_qt6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:eye" /></template>
