<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kngzmjb8s.css';
import '../../css/g/g0-11mmdk.css';
import '../../css/g/g23e_tb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kngzmjb8s"/><path class="g0-11mmdk"/><path class="g23e_tb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:box-bold-duotone" /></template>
