<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-11jrk6e.css';
import '../../css/z/zx7fs7byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="j-11jrk6e"/><path clip-rule="evenodd" class="zx7fs7byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:alpinejs" /></template>
