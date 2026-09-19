<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjahfzb-f.css';
import '../../css/n/nb1ykgawv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hjahfzb-f"/><path class="nb1ykgawv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:leaf-sharp" /></template>
