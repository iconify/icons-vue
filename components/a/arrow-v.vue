<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijj-5e42m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijj-5e42m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:arrow-v" /></template>
