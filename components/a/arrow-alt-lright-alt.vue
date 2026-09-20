<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp66c-b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp66c-b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:arrow-alt-lright-alt" /></template>
