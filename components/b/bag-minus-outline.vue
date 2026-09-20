<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf92_rw-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pf92_rw-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bag-minus-outline" /></template>
