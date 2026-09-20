<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu-a57w1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="zu-a57w1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:landmark-jp-11" /></template>
