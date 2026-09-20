<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htc8-3ocq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htc8-3ocq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ankermake" /></template>
