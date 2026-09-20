<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f11wjqhij.css';
import '../../css/o/oimetacyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f11wjqhij"/><path class="oimetacyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:discount-percent-bubble" /></template>
