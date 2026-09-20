<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzolh-kgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzolh-kgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:dimond" /></template>
