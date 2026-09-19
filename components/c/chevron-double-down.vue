<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhm0ndz3m.css';
import '../../css/v/vw4ng7gqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yhm0ndz3m"/><path class="vw4ng7gqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chevron-double-down" /></template>
