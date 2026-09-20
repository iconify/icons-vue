<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq80f2hmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kq80f2hmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:heart-with-bolt" /></template>
