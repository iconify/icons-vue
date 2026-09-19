<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae8y8wkyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ae8y8wkyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gym-bag" /></template>
