<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cquyq257a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cquyq257a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:corner-up-left-solid" /></template>
