<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdy0hsr3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdy0hsr3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:libreoffice" /></template>
