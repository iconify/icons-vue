<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3jslumyd.css';
import '../../css/t/tzc9byxdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3jslumyd"/><path class="tzc9byxdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:bag" /></template>
