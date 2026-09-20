<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixxc27uve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixxc27uve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book" /></template>
