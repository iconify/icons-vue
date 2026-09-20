<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/polv-0les.css';
import '../../css/f/fsw0aeb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="polv-0les"/><path class="fsw0aeb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:last-updates-solid" /></template>
