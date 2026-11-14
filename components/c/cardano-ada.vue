<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odrrekjno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odrrekjno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:cardano-ada" /></template>
