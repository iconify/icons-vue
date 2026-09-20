<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmo45hhmm.css';
import '../../css/h/hb4vkiz6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tmo45hhmm"/><path class="hb4vkiz6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:cloud-up-16" /></template>
