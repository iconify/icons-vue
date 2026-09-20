<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4b69pz9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n4b69pz9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:happy-face-with-face-mask" /></template>
