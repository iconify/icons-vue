<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-bjbachs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-bjbachs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-top-detailed-line" /></template>
