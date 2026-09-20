<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4esp7b2q.css';
import '../../css/i/im-69xmjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u4esp7b2q"/><path class="im-69xmjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:feeds-fun-dark" /></template>
