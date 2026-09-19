<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/capx64hcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="capx64hcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:heart-alt" /></template>
