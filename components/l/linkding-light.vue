<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap5--l7rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ap5--l7rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linkding-light" /></template>
