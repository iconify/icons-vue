<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oquc4acgh.css';
import '../../css/y/yk5n1ybrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oquc4acgh"/><path class="yk5n1ybrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:feed-light" /></template>
