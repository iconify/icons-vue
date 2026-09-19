<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_cj-5b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_cj-5b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-up-left-box-outline" /></template>
