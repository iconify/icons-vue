<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5kwrbb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l5kwrbb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:brush-outline" /></template>
