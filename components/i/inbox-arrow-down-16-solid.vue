<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzevmeb7i.css';
import '../../css/q/q2sfcejqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pzevmeb7i"/><path class="q2sfcejqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:inbox-arrow-down-16-solid" /></template>
