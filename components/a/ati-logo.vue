<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwj4rxbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwj4rxbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:ati-logo" /></template>
