<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vipa3vb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vipa3vb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlev" /></template>
