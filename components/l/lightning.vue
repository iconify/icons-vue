<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1wpmri9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1wpmri9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lightning" /></template>
