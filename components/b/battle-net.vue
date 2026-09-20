<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaiqf7u2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vaiqf7u2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:battle-net" /></template>
