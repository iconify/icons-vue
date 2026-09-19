<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji4dzvl8f.css';
import '../../css/b/bzl494b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ji4dzvl8f"/><path class="bzl494b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-game-controller-b" /></template>
