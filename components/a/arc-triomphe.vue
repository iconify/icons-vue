<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx-iusb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jx-iusb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:arc-triomphe" /></template>
