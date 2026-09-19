<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmcm0s1it.css';
import '../../css/h/hmryub9or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path transform="matrix(.92099 0 0 .92169 -.41 .382)" class="bmcm0s1it"/><path class="hmryub9or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:cursor-ignore" /></template>
