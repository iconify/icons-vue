<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysp7eum_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysp7eum_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:angularuniversal" /></template>
