<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq53nzb0t.css';
import '../../css/d/dnwwjhmil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fq53nzb0t"/><path class="dnwwjhmil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:divide-16-solid" /></template>
