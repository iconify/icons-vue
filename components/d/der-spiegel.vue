<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h93thl7yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h93thl7yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:der-spiegel" /></template>
