<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s89hj8brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s89hj8brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clock-hour-3" /></template>
