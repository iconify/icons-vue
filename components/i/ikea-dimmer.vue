<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syoi-0qiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syoi-0qiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-dimmer" /></template>
