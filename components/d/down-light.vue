<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwi__9bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwi__9bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:down-light" /></template>
