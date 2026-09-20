<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lozn8dbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lozn8dbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cake-1" /></template>
