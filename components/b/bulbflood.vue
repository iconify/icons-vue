<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpeveur9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpeveur9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulbflood" /></template>
