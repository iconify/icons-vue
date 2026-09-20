<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whmt9g0aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whmt9g0aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bulma" /></template>
