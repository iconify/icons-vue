<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_57x5kqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_57x5kqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clock-hour-12-filled" /></template>
