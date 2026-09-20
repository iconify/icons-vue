<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcud33_8u.css';
import '../../css/c/cpy2d7b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vcud33_8u"/><path clip-rule="evenodd" class="cpy2d7b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:google-ad-solid" /></template>
