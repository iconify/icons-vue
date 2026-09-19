<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk15ubb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qk15ubb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:concrete-bag" /></template>
