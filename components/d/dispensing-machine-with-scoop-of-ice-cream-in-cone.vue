<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifmbnfnsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ifmbnfnsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dispensing-machine-with-scoop-of-ice-cream-in-cone" /></template>
