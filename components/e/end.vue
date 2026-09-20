<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hon-ku8jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="hon-ku8jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:end" /></template>
