<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx2t855jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx2t855jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-2" /></template>
