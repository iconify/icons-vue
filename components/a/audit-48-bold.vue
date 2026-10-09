<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwgv7ib-v.css';
import '../../css/v/vk1vhpblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jwgv7ib-v"/><path class="vk1vhpblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:audit-48-bold" /></template>
