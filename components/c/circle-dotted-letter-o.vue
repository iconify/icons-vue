<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk32wkbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk32wkbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dotted-letter-o" /></template>
