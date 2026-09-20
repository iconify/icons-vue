<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpefq04rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpefq04rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:escalator-filled" /></template>
