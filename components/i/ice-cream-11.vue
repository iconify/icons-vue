<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxtbdh8eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="sxtbdh8eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:ice-cream-11" /></template>
