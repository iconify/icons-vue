<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zijpg8o5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zijpg8o5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:diaspora" /></template>
