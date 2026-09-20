<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x70d-ut1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x70d-ut1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kickstarter" /></template>
