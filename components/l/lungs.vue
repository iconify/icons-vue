<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhr__acdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xhr__acdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:lungs" /></template>
