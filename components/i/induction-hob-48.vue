<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsmhpgwcs.css';
import '../../css/d/dmi2w96im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tsmhpgwcs"/><path class="dmi2w96im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:induction-hob-48" /></template>
