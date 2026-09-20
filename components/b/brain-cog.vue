<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6q2pl6bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6q2pl6bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:brain-cog" /></template>
