<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv01ljeqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jv01ljeqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:face-sad-cry" /></template>
