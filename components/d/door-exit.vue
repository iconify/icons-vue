<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft2zvc91t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft2zvc91t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:door-exit" /></template>
