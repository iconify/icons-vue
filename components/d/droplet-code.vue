<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe5ax8ult.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe5ax8ult"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-code" /></template>
