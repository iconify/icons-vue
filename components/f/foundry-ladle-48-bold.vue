<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8zb0dyhn.css';
import '../../css/e/eb2y314nt.css';
import '../../css/i/ihmii9b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i8zb0dyhn"/><path class="eb2y314nt"/><path class="ihmii9b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:foundry-ladle-48-bold" /></template>
