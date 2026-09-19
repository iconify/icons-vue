<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp-5fvbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp-5fvbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:contra" /></template>
