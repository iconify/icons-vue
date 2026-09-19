<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny4kt2vec.css';
import '../../css/i/i_o33ybmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny4kt2vec"/><path class="i_o33ybmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:checked-box-outline" /></template>
