<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in6jc3bsu.css';
import '../../css/z/z46kgibda.css';
import '../../css/p/p4x9h9btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in6jc3bsu"/><path class="z46kgibda"/><path class="p4x9h9btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:agrs" /></template>
