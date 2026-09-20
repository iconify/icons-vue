<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf2o4ub-c.css';
import '../../css/a/aklkyaciw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf2o4ub-c"/><path class="aklkyaciw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:compass-1-bold" /></template>
