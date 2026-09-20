<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5wn405-h.css';
import '../../css/b/bed8vacuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="d5wn405-h"/><path class="bed8vacuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-ambulance" /></template>
