<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egwfgir1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egwfgir1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:co2" /></template>
