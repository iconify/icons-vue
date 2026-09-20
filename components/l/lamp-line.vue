<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5bck-xcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5bck-xcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:lamp-line" /></template>
