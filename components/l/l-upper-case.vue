<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imkwy3-et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":454,"height":735};
const content = `<path class="imkwy3-et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:l-upper-case" /></template>
