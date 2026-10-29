<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btv40kbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btv40kbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-chevron-left-solid" /></template>
