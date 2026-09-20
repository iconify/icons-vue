<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9aeyhb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9aeyhb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:fridge-line" /></template>
