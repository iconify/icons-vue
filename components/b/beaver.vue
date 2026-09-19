<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owps0zbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="owps0zbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:beaver" /></template>
