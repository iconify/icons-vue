<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynacwacmn.css';
import '../../css/k/kmd5rqb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ynacwacmn"/><path class="kmd5rqb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:mail-open-outline" /></template>
