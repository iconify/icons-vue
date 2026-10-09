<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve7dckibf.css';
import '../../css/d/dl48ttr9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ve7dckibf"/><path class="dl48ttr9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hair-dryer-48-bold" /></template>
