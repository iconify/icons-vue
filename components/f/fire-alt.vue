<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pez3-pb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pez3-pb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fire-alt" /></template>
