<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia2agsb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-6,"top":-7.5};
const content = `<path class="ia2agsb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:color" /></template>
