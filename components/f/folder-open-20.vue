<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbu-gbckp.css';
import '../../css/t/t9c8c1b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xbu-gbckp"/><path class="t9c8c1b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-open-20" /></template>
