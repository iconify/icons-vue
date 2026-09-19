<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb5pocb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="vb5pocb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:boxing" /></template>
