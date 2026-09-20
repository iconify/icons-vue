<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohmyqd7eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ohmyqd7eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hospital-outline" /></template>
