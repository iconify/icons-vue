<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-jap0buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j-jap0buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-firefly-light" /></template>
