<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwldzvb5c.css';
import '../../css/s/spys-wb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="rwldzvb5c"/><path class="spys-wb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:first-aid-alt" /></template>
