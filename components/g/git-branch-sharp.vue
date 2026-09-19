<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxc1hnbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bxc1hnbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:git-branch-sharp" /></template>
