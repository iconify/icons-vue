<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szahujb-p.css';
import '../../css/s/sm8tyk6uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="szahujb-p"/><path class="sm8tyk6uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-sparkle-20" /></template>
