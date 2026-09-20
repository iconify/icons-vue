<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2oa95zkl.css';
import '../../css/x/xxvlnybzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="f2oa95zkl"/><path class="xxvlnybzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:battery-5-solid" /></template>
