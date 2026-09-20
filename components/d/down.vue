<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynj2_0btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynj2_0btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:down" /></template>
