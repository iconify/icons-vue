<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4gygqbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="s4gygqbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:compass-small" /></template>
