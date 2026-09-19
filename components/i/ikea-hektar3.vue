<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx7e5vbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx7e5vbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-hektar3" /></template>
