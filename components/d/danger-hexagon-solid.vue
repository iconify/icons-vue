<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2lxpi_vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2lxpi_vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:danger-hexagon-solid" /></template>
