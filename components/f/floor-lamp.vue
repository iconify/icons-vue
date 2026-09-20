<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzned5b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zzned5b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:floor-lamp" /></template>
