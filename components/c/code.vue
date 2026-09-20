<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghra1q62g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ghra1q62g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:code" /></template>
