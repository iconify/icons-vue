<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n73m8acuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n73m8acuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-left-16-solid" /></template>
