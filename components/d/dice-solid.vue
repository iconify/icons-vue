<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruy1hxbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ruy1hxbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dice-solid" /></template>
