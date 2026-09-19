<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1r7rub3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1r7rub3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-uppatvind" /></template>
