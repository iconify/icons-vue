<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x94bwmbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x94bwmbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:direction-sign-off" /></template>
