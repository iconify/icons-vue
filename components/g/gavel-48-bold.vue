<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir7tugprl.css';
import '../../css/t/tnnq4zbbd.css';
import '../../css/o/o6n1tfudy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ir7tugprl"/><path class="tnnq4zbbd"/><path class="o6n1tfudy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gavel-48-bold" /></template>
