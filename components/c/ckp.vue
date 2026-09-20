<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9xp5f9ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9xp5f9ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ckp" /></template>
