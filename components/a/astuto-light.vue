<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr-71ib7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hr-71ib7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:astuto-light" /></template>
