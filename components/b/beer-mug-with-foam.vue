<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8iyr9bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n8iyr9bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:beer-mug-with-foam" /></template>
