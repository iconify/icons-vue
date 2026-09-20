<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsx-hsbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsx-hsbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:actix" /></template>
