<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7q2uubrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7q2uubrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:colab-google" /></template>
