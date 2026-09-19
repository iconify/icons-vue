<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-opqmvpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":614};
const content = `<path class="q-opqmvpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fishbone" /></template>
