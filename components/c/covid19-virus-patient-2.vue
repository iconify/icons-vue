<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4tiu56qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4tiu56qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:covid19-virus-patient-2" /></template>
