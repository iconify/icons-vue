<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq1x5_nht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qq1x5_nht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:hand-16" /></template>
