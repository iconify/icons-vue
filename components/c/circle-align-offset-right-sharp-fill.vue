<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff8cuy0tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ff8cuy0tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-align-offset-right-sharp-fill" /></template>
