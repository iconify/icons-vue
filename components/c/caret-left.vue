<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odz7kjb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="odz7kjb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:caret-left" /></template>
