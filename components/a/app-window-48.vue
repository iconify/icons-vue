<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3q6uacna.css';
import '../../css/d/dib-0nbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v3q6uacna"/><path class="dib-0nbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:app-window-48" /></template>
