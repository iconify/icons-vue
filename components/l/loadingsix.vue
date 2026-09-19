<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx6fch0-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vx6fch0-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:loadingsix" /></template>
