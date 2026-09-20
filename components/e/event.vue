<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp7lv3bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lp7lv3bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:event" /></template>
