<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb4ipdb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="kb4ipdb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:alarmclock" /></template>
