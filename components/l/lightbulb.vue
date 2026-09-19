<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maqn9jbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="maqn9jbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:lightbulb" /></template>
