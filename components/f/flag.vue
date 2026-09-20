<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_ew2zboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_ew2zboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:flag" /></template>
