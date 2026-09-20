<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj0mq3b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj0mq3b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:database-line" /></template>
