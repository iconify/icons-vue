<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cceytw1-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cceytw1-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:akasa-air" /></template>
