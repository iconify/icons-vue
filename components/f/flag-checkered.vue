<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz_reeb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tz_reeb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:flag-checkered" /></template>
