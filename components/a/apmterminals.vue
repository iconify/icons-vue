<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_gz41biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_gz41biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:apmterminals" /></template>
