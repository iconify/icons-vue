<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqb7atbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqb7atbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:check-duotone" /></template>
