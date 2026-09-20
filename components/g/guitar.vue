<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sio_2yb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="sio_2yb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:guitar" /></template>
