<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2pa488uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2pa488uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:form-refresh" /></template>
