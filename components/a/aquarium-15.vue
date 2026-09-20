<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g60ojkb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g60ojkb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:aquarium-15" /></template>
