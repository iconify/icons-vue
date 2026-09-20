<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmry91get.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmry91get"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-left-up-line" /></template>
