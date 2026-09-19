<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmuk_416i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bmuk_416i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-4-clubs" /></template>
