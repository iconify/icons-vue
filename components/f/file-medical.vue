<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9jw3ozbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9jw3ozbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-medical" /></template>
