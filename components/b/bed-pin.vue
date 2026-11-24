<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afb1-qlef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afb1-qlef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bed-pin" /></template>
