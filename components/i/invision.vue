<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5747cl7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="o5747cl7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:invision" /></template>
