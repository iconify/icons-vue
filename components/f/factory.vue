<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0tz0buop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="j0tz0buop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:factory" /></template>
