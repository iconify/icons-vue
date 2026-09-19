<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kra7neb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":758};
const content = `<path class="kra7neb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:bell" /></template>
