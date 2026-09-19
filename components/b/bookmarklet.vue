<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9m4fkb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y9m4fkb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bookmarklet" /></template>
