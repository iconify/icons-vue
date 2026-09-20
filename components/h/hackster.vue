<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5ilamxla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5ilamxla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hackster" /></template>
