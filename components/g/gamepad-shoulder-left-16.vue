<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aieknlrza.css';
import '../../css/p/p-1znlk9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aieknlrza"/><path clip-rule="evenodd" class="p-1znlk9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gamepad-shoulder-left-16" /></template>
