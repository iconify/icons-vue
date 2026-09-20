<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgff4ownd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgff4ownd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:currency-gbp" /></template>
