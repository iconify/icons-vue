<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icrxpc5-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="icrxpc5-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:connected" /></template>
