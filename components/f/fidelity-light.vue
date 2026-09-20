<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3sn0bzum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v3sn0bzum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fidelity-light" /></template>
