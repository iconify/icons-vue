<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt57vq-0m.css';
import '../../css/i/iorf33r0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wt57vq-0m"/><path class="iorf33r0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:battery-half-sharp" /></template>
