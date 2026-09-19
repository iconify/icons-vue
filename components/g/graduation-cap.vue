<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it_isbcep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it_isbcep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:graduation-cap" /></template>
