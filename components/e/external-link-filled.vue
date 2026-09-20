<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juul3ub7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juul3ub7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:external-link-filled" /></template>
