<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sav88e29u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sav88e29u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:glances-alt" /></template>
