<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh6e5bcgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh6e5bcgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:equal" /></template>
