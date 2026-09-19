<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtzdz7blb.css';
import '../../css/l/l06wekb2j.css';
import '../../css/f/ff7iaab8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vtzdz7blb"/><path class="l06wekb2j"/><path class="ff7iaab8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-tableau" /></template>
