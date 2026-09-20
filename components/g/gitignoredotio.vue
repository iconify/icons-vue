<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcr3pm8qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcr3pm8qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gitignoredotio" /></template>
