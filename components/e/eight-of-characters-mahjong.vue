<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li0c3jbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="li0c3jbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:eight-of-characters-mahjong" /></template>
