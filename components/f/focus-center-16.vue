<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylhdevp5c.css';
import '../../css/v/v-gec3bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ylhdevp5c"/><path class="v-gec3bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:focus-center-16" /></template>
