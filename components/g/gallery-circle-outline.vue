<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekffpejwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ekffpejwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-circle-outline" /></template>
