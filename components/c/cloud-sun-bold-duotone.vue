<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb7vvlbro.css';
import '../../css/y/y7ajkhrwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="qb7vvlbro"/><path class="y7ajkhrwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-sun-bold-duotone" /></template>
