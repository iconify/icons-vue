<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg-d9bb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg-d9bb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-sharp-duotone" /></template>
