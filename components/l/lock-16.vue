<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt58u3bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pt58u3bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:lock-16" /></template>
