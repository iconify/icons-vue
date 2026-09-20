<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hem1vcbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hem1vcbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:edit-bulk" /></template>
