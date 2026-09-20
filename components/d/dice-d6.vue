<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2w_62b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c2w_62b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dice-d6" /></template>
