<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmc0sccxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmc0sccxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:call-end" /></template>
