<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egirhzbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="egirhzbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:images-alt2" /></template>
