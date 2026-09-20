<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7xoszsbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7xoszsbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:door-hanger" /></template>
