<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acw94x52i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acw94x52i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brackets-angle-line" /></template>
