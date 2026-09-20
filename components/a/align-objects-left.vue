<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltzgmpb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ltzgmpb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:align-objects-left" /></template>
