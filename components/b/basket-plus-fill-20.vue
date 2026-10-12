<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxm-7vagy.css';
import '../../css/r/r3cn_9bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lxm-7vagy"/><path class="r3cn_9bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:basket-plus-fill-20" /></template>
