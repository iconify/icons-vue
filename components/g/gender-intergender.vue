<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vves_obdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vves_obdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:gender-intergender" /></template>
