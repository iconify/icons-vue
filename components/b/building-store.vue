<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmrm4zbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmrm4zbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-store" /></template>
