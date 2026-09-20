<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdc9n4l0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdc9n4l0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-minus" /></template>
