<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suj0jjbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suj0jjbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ancient-gate-fill" /></template>
