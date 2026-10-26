<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty-ubbn8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ty-ubbn8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:chat" /></template>
