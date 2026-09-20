<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyxmmfrwe.css';
import '../../css/x/xxvlnybzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qyxmmfrwe"/><path class="xxvlnybzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:battery-1-solid" /></template>
