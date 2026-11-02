<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmk3y5beo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmk3y5beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:inbox-2-fill" /></template>
