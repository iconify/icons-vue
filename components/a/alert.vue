<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_n30w53s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_n30w53s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:alert" /></template>
