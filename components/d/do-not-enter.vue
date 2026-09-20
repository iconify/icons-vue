<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu07fk1vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu07fk1vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:do-not-enter" /></template>
