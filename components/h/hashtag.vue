<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vueoze_al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vueoze_al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:hashtag" /></template>
