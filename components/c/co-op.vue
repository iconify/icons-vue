<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/islf9fwnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="islf9fwnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:co-op" /></template>
