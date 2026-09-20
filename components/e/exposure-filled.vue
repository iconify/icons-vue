<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u25v2e26i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u25v2e26i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:exposure-filled" /></template>
