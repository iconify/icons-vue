<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v69l6yjwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v69l6yjwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:csdn" /></template>
