<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsr6lsg6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsr6lsg6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flask-off" /></template>
