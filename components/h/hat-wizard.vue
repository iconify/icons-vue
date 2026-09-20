<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7adn7brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c7adn7brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hat-wizard" /></template>
