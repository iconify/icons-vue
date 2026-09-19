<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfmvkpkva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zfmvkpkva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:less-than-equal" /></template>
