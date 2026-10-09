<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7m3rdb3k.css';
import '../../css/s/s9upufoui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z7m3rdb3k"/><path class="s9upufoui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:burger-20-bold" /></template>
