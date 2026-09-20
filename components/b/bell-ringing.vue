<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-02fkubu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="i-02fkubu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:bell-ringing" /></template>
