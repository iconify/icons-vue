<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puo94vz7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":512};
const content = `<path class="puo94vz7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:gofore" /></template>
