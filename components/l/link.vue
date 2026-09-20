<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee35q2bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee35q2bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:link" /></template>
