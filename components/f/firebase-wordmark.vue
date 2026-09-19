<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqoz608tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bqoz608tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:firebase-wordmark" /></template>
