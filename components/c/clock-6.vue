<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqhz7ib8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqhz7ib8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clock-6" /></template>
