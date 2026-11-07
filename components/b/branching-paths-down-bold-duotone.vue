<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg928d-qd.css';
import '../../css/x/xitusjssr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path class="xitusjssr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:branching-paths-down-bold-duotone" /></template>
