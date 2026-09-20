<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz050sboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zz050sboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:expand-outline" /></template>
