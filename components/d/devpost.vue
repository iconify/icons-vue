<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zndtekn6f.css';
import '../../css/c/c1_dnpbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zndtekn6f"/><path class="c1_dnpbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:devpost" /></template>
