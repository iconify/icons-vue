<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brxv_3lse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="brxv_3lse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:eye-with-line" /></template>
