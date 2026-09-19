<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl9hx3b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="kl9hx3b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:caret-down" /></template>
