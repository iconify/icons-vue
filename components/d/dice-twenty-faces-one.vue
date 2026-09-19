<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu6oghb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wu6oghb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dice-twenty-faces-one" /></template>
