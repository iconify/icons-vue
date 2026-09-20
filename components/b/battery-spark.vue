<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdldd8buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdldd8buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-spark" /></template>
