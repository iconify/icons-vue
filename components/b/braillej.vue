<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g07rnibyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="g07rnibyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:braillej" /></template>
