<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6v0-ubfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6v0-ubfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aldi-sued" /></template>
