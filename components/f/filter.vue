<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqcchrbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqcchrbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:filter" /></template>
