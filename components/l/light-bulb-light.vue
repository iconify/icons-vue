<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6dzq6bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6dzq6bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:light-bulb-light" /></template>
