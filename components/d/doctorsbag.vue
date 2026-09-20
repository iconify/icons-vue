<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9cz7dbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="c9cz7dbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:doctorsbag" /></template>
