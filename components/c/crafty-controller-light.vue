<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guz2q5bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="guz2q5bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crafty-controller-light" /></template>
