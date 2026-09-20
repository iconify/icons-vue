<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1ozk6l8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a1ozk6l8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:framadate-dark" /></template>
