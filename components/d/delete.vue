<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8_9bkb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="a8_9bkb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:delete" /></template>
