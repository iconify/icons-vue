<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk3yj5b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk3yj5b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clock-hour-4" /></template>
