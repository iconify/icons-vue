<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgm64nolf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bgm64nolf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:android-mask" /></template>
