<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw-3q14fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw-3q14fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:jhipster" /></template>
