<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ravrb1b2k.css';
import '../../css/s/s9p5b8y_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ravrb1b2k"/><path class="s9p5b8y_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:database-zap-filled" /></template>
