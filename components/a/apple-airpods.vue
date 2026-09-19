<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa212acpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa212acpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:apple-airpods" /></template>
