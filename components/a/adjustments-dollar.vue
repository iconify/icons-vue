<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v--48wqcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v--48wqcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:adjustments-dollar" /></template>
