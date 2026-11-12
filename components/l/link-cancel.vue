<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l36mhpb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l36mhpb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:link-cancel" /></template>
