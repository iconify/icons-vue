<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyospdzkg.css';
import '../../css/r/r5r1i95ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyospdzkg"/><path class="r5r1i95ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:badge-dollar-duotone" /></template>
