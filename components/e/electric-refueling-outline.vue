<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha7uky3jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ha7uky3jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:electric-refueling-outline" /></template>
