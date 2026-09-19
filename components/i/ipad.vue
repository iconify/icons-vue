<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdolti6_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="mdolti6_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:ipad" /></template>
