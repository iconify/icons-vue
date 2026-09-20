<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtu2yutov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtu2yutov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:99designs" /></template>
