<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqgq8bbqo.css';
import '../../css/k/kys9qibdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="pqgq8bbqo"/><path class="kys9qibdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:comment-minus" /></template>
