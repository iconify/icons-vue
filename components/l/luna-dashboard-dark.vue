<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbp06qb8h.css';
import '../../css/h/hpzn55bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rbp06qb8h"/><path class="hpzn55bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:luna-dashboard-dark" /></template>
