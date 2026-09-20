<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmu9l7bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmu9l7bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-bank" /></template>
