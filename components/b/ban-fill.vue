<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv7eq8pia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv7eq8pia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ban-fill" /></template>
