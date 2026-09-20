<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of7v_qbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="of7v_qbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-horiz-center-detailed-fill" /></template>
