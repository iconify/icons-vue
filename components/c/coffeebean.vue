<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kelnhhbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1026};
const content = `<path class="kelnhhbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:coffeebean" /></template>
