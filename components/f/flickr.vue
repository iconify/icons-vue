<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z83o5xbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z83o5xbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:flickr" /></template>
