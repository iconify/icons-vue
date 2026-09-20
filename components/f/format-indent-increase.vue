<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anl7xs23s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anl7xs23s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-indent-increase" /></template>
