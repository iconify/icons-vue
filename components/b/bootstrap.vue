<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1ug-9b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1ug-9b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bootstrap" /></template>
