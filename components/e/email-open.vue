<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rosrm6b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rosrm6b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:email-open" /></template>
