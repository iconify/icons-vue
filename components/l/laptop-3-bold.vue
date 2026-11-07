<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_78m3epb.css';
import '../../css/c/cq7nq2bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_78m3epb"/><path class="cq7nq2bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:laptop-3-bold" /></template>
