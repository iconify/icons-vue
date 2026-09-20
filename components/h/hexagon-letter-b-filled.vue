<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scjpqqb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scjpqqb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-b-filled" /></template>
