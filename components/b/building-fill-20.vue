<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_6gdx37i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s_6gdx37i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:building-fill-20" /></template>
