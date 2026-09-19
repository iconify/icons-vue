<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee_489afo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee_489afo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-for-marketing" /></template>
