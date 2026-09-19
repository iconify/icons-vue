<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6fooktbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n6fooktbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:basset-hound-head" /></template>
