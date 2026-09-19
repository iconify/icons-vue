<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9mebwb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9mebwb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ascaso-steel-duo" /></template>
