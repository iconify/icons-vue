<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bem_48t0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bem_48t0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:city" /></template>
