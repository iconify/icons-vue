<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqh_f-kog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqh_f-kog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-commit-solid" /></template>
