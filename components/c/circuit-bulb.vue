<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvw_drbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvw_drbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circuit-bulb" /></template>
