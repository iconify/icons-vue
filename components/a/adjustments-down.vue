<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otsyogwwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otsyogwwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:adjustments-down" /></template>
