<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi5d4zb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi5d4zb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:laravelnova" /></template>
