<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yydbcv1gz.css';
import '../../css/x/xxvlnybzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="yydbcv1gz"/><path class="xxvlnybzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:battery-charge-solid" /></template>
