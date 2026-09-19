<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfn9nbjqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jfn9nbjqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:harpoon-trident" /></template>
