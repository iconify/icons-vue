<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vry51s4gb.css';
import '../../css/w/wxx5nhb-e.css';
import '../../css/a/amd21sbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<circle class="vry51s4gb"/><circle class="wxx5nhb-e"/><path class="amd21sbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:drink" /></template>
