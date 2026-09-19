<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqyo_428x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vqyo_428x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:flickr-with-circle" /></template>
