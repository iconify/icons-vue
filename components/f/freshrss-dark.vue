<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zev9aeikb.css';
import '../../css/v/vprbqcbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zev9aeikb"/><path class="vprbqcbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freshrss-dark" /></template>
