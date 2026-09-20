<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8twl3rcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8twl3rcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:forward" /></template>
