<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn8k0jbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn8k0jbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-right-large-duocolor-round" /></template>
