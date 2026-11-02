<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd6t3v_tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd6t3v_tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:group-2-line" /></template>
