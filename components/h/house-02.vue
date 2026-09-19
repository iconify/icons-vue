<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdfie47xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdfie47xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:house-02" /></template>
