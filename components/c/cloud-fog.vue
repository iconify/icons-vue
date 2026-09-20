<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snv4fbb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snv4fbb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cloud-fog" /></template>
