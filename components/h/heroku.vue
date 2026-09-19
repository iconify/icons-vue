<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttxo0tbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttxo0tbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:heroku" /></template>
