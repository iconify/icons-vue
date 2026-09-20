<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av2burbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av2burbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:creative-commons-sa-fill" /></template>
