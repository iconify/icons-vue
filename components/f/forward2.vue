<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfstxhi3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kfstxhi3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:forward2" /></template>
