<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h909xs_ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h909xs_ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:dev-to" /></template>
