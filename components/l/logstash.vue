<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgmq7_xxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tgmq7_xxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:logstash" /></template>
