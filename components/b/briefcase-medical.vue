<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om2x0ob5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om2x0ob5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:briefcase-medical" /></template>
