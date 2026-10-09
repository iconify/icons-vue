<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljpp4jbkd.css';
import '../../css/j/jmkpn4wvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ljpp4jbkd"/><path class="jmkpn4wvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-flare-20" /></template>
