<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0b7glbxa.css';
import '../../css/z/zyv9ekbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b0b7glbxa"/><path class="zyv9ekbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:android-fill-16" /></template>
