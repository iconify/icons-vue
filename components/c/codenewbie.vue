<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy28hvb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy28hvb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:codenewbie" /></template>
