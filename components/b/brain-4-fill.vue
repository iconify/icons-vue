<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-tn6absb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-tn6absb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brain-4-fill" /></template>
