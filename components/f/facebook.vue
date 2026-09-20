<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnt67v5tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="pnt67v5tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:facebook" /></template>
